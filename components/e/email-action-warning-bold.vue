<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd5i1ccgy.css';
import '../../css/b/bp38xibkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd5i1ccgy"/><path class="bp38xibkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:email-action-warning-bold" /></template>
