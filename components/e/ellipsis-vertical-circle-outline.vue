<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuejpjjmz.css';
import '../../css/r/r6fga5szw.css';
import '../../css/u/ualmvtb9v.css';
import '../../css/l/lsg5j7ibl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="vuejpjjmz"/><circle class="r6fga5szw"/><circle class="ualmvtb9v"/><path class="lsg5j7ibl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ellipsis-vertical-circle-outline" /></template>
