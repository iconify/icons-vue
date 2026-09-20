<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0zocwx_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l0zocwx_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-6-sharp-fill" /></template>
