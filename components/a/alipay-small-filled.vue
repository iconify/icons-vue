<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbnmv6zzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="nbnmv6zzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:alipay-small-filled" /></template>
