<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz_l2cbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz_l2cbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-remove-outline" /></template>
