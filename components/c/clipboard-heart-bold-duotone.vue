<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo43we00a.css';
import '../../css/g/gnkxcd53d.css';
import '../../css/c/c4946-17v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo43we00a"/><path class="gnkxcd53d"/><path class="c4946-17v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-heart-bold-duotone" /></template>
