<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr_4lkqsn.css';
import '../../css/k/kwj8pfbpn.css';
import '../../css/x/xqzgogbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr_4lkqsn"/><path class="kwj8pfbpn"/><path class="xqzgogbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:flip-v-alt" /></template>
