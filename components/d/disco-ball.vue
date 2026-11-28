<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwcejpn7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwcejpn7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:disco-ball" /></template>
