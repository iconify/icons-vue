<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv-ekvb3r.css';
import '../../css/y/yze3d2bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv-ekvb3r"/><path class="yze3d2bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-swipe-up-filled" /></template>
