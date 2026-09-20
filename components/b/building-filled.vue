<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci8y9zdxq.css';
import '../../css/p/p2cix6gor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci8y9zdxq"/><path class="p2cix6gor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:building-filled" /></template>
