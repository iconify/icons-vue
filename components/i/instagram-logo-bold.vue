<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu_ca8b3i.css';
import '../../css/r/r-h8u5bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu_ca8b3i"/><path class="r-h8u5bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:instagram-logo-bold" /></template>
