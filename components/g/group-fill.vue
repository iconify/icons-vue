<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro4pgpygn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro4pgpygn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:group-fill" /></template>
