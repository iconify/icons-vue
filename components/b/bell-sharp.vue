<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dda_q--5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dda_q--5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-sharp" /></template>
