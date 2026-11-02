<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfgih6lsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfgih6lsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:baggage-claim-fill" /></template>
