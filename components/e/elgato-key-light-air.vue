<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygzf0o_ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygzf0o_ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:elgato-key-light-air" /></template>
