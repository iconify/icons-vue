<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qel0gob0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qel0gob0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:expand-vertical-solid" /></template>
