<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krckgcb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krckgcb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:chicken-coop" /></template>
