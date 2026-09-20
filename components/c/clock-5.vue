<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygwp1gb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygwp1gb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-5" /></template>
