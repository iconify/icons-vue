<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nayue9sxw.css';
import '../../css/v/vpnv4ccxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nayue9sxw"/><path class="vpnv4ccxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-ionic-outline" /></template>
