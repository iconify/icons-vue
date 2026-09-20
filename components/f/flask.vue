<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no6tox70b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no6tox70b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flask" /></template>
