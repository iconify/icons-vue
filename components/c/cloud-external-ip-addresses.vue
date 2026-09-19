<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqle1m17k.css';
import '../../css/d/dw1rn2v6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqle1m17k"/><path class="dw1rn2v6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-external-ip-addresses" /></template>
