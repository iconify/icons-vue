<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yas0kcb_a.css';
import '../../css/s/sz0y6ba_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yas0kcb_a"/><path class="sz0y6ba_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:content-paper-edit-bold" /></template>
