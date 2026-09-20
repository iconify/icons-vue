<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud5o94vem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud5o94vem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:application-filled" /></template>
