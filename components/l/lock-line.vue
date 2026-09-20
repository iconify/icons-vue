<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6xo7s8ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6xo7s8ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:lock-line" /></template>
