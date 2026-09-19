<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wadt5k89n.css';
import '../../css/l/li7_vqt7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wadt5k89n"/><path class="li7_vqt7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-alarm-outline" /></template>
