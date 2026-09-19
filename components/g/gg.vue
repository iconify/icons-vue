<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czww5qr0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":34,"height":24};
const content = `<path class="czww5qr0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:gg" /></template>
