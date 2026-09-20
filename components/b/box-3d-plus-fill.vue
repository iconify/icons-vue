<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnx5z5buf.css';
import '../../css/q/qhqeaxbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnx5z5buf"/><path class="qhqeaxbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-3d-plus-fill" /></template>
