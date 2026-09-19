<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdzz6xdbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdzz6xdbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:elgato-key-light" /></template>
