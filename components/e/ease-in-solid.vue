<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwkyo7u3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwkyo7u3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ease-in-solid" /></template>
