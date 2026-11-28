<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs0n83b1m.css';
import '../../css/b/bats-ew3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs0n83b1m secondary"/><path class="bats-ew3c primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:diamond-duo" /></template>
