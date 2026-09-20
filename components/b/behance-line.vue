<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl8xurxvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl8xurxvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:behance-line" /></template>
