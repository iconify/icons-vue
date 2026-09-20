<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl_78bb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl_78bb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:digitalocean" /></template>
