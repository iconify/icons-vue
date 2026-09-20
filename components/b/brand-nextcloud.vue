<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbq-nhb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbq-nhb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-nextcloud" /></template>
