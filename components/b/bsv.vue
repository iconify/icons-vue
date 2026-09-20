<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxkz9nbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxkz9nbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bsv" /></template>
