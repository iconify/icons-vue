<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf9-5_bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf9-5_bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:appletv-gen2-remote" /></template>
