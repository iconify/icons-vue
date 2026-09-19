<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov4mpzb8r.css';
import '../../css/y/y3xz-nb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ov4mpzb8r"/><path class="y3xz-nb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:book-open-solid" /></template>
