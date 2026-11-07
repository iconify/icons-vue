<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kflf7crkg.css';
import '../../css/m/mimh63b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kflf7crkg"/><path class="mimh63b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-chat-rounded-bold" /></template>
