<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kye07wy2c.css';
import '../../css/b/bz70mjb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kye07wy2c"/><path clip-rule="evenodd" class="bz70mjb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-favourite-bold" /></template>
