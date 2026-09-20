<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2lg_ora.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_2lg_ora"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:facebook-f" /></template>
