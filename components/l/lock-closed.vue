<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4kkrfgux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="z4kkrfgux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:lock-closed" /></template>
