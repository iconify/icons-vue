<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2j_krb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2j_krb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ad-circle-off-line" /></template>
