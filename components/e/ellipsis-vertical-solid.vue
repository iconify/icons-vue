<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blci9d4-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="blci9d4-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:ellipsis-vertical-solid" /></template>
