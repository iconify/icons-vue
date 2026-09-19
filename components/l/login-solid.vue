<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4nt_319i.css';
import '../../css/t/tv2_2htnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4nt_319i"/><path class="tv2_2htnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:login-solid" /></template>
