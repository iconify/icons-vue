<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1j0aebsi.css';
import '../../css/s/sq9kvubup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1j0aebsi"/><path class="sq9kvubup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:discord-chat" /></template>
