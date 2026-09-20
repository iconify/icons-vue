<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snp287xku.css';
import '../../css/p/pp8nmdb7j.css';
import '../../css/k/k5loyzbkf.css';
import '../../css/w/w5u46jbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="snp287xku"/><path class="pp8nmdb7j"/><path class="k5loyzbkf"/><path class="w5u46jbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:diamond-suit" /></template>
