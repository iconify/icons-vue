<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw5ygun_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw5ygun_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:blogger" /></template>
