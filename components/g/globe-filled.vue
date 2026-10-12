<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgw916bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgw916bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:globe-filled" /></template>
