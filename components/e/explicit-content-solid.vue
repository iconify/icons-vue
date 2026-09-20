<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go2_u_qmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go2_u_qmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:explicit-content-solid" /></template>
