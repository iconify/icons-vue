<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oljebpb3g.css';
import '../../css/y/y_g1oe_0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oljebpb3g"/><path class="y_g1oe_0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:exclamation-alert" /></template>
