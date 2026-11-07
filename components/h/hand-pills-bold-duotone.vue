<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7qi5pmcg.css';
import '../../css/b/b7scrfump.css';
import '../../css/b/b-tlngp_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7qi5pmcg"/><path class="b7scrfump"/><path class="b-tlngp_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-pills-bold-duotone" /></template>
