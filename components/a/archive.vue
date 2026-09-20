<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml95i05tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml95i05tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:archive" /></template>
