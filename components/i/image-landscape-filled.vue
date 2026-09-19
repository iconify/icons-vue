<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk_r7tbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk_r7tbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:image-landscape-filled" /></template>
