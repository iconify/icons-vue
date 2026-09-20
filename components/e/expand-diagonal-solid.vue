<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh6f6cz1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh6f6cz1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:expand-diagonal-solid" /></template>
