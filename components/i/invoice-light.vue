<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5ijgqb1h.css';
import '../../css/t/tgz0bac_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5ijgqb1h"/><path class="tgz0bac_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:invoice-light" /></template>
