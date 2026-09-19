<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqx63bc5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hqx63bc5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:eye-dropper-20-solid" /></template>
