<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd-wwxbtw.css';
import '../../css/c/c4946-17v.css';
import '../../css/m/mo43we00a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd-wwxbtw"/><path class="c4946-17v"/><path class="mo43we00a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-type-bold-duotone" /></template>
