<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_nt2_bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_nt2_bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cancel-circle-multiple-outline" /></template>
