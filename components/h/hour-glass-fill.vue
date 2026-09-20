<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw_gay31a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw_gay31a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:hour-glass-fill" /></template>
