<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el_l0sbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el_l0sbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-adobe-lightroom-filled" /></template>
