<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzzv-dbod.css';
import '../../css/v/v19mbwu8m.css';
import '../../css/p/pbaa7xb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzzv-dbod"/><path class="v19mbwu8m"/><path class="pbaa7xb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kan" /></template>
