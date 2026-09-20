<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbs_lyb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbs_lyb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-wireless-80" /></template>
