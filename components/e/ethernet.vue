<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_z5thb8t.css';
import '../../css/t/tuliz9bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_z5thb8t"/><path class="tuliz9bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ethernet" /></template>
