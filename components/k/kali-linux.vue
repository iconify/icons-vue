<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3y9ae9qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3y9ae9qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kali-linux" /></template>
