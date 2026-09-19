<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb59htb_d.css';
import '../../css/k/k4or6zb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb59htb_d"/><path clip-rule="evenodd" class="k4or6zb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:key-outline" /></template>
