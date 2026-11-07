<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw1zzn-6t.css';
import '../../css/r/ra2ravfoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw1zzn-6t"/><path class="ra2ravfoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbells-2-bold" /></template>
