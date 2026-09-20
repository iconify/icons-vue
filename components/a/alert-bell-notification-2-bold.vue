<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my86mbcer.css';
import '../../css/v/v5iwbub1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my86mbcer"/><path class="v5iwbub1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:alert-bell-notification-2-bold" /></template>
