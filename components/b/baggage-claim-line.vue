<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8cenbbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8cenbbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:baggage-claim-line" /></template>
