<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpltfcc5a.css';
import '../../css/e/ee1w0tnkd.css';
import '../../css/y/yyu6w0k1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpltfcc5a"/><path clip-rule="evenodd" class="ee1w0tnkd"/><path class="yyu6w0k1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-search-filled" /></template>
