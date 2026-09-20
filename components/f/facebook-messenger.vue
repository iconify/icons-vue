<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7h7v2bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7h7v2bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:facebook-messenger" /></template>
