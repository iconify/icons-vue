<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za8-4ob-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za8-4ob-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:artemide-nessino" /></template>
