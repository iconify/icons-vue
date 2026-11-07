<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1-qbmafx.css';
import '../../css/u/ul-233bzy.css';
import '../../css/d/dbfay--fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1-qbmafx"/><path class="ul-233bzy"/><path clip-rule="evenodd" class="dbfay--fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-bottom-bold-duotone" /></template>
