<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li7no0b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li7no0b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-check" /></template>
