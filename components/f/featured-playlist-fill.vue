<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sms47jbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sms47jbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:featured-playlist-fill" /></template>
