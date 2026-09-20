<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovb3_79qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovb3_79qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:behance-alt" /></template>
