<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_ezh736y.css';
import '../../css/w/wtxugid0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_ezh736y"/><path class="wtxugid0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cloud-check-light" /></template>
