<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knv9mypjn.css';
import '../../css/o/oao8y4zzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="knv9mypjn"/><path class="oao8y4zzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hyperpipe" /></template>
