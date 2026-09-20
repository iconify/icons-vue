<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps4tf-iae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps4tf-iae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-twitter-filled" /></template>
