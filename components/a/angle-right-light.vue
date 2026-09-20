<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_rxwab-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_rxwab-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:angle-right-light" /></template>
