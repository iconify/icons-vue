<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4spl7m6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4spl7m6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gamma" /></template>
