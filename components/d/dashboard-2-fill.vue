<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkiqt7bnd.css';
import '../../css/k/k06qbne_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkiqt7bnd"/><path class="k06qbne_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dashboard-2-fill" /></template>
