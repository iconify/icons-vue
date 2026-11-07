<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4tjy3b9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4tjy3b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:end-call-rounded-broken" /></template>
