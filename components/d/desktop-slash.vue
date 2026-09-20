<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj-6kbbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj-6kbbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:desktop-slash" /></template>
