<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdkk788_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdkk788_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-android-filled" /></template>
