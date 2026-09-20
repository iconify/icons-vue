<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n90uq3bfu.css';
import '../../css/l/ljkivvbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n90uq3bfu"/><path class="ljkivvbav ouiIcon__fillSecondary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-recently-viewed" /></template>
