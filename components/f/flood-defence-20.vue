<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laitt1gtv.css';
import '../../css/t/tqdr_mbdb.css';
import '../../css/k/k153fdm9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="laitt1gtv"/><path class="tqdr_mbdb"/><path class="k153fdm9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flood-defence-20" /></template>
