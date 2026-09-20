<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi68c0nhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oi68c0nhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lock-password-filled" /></template>
