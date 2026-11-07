<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_as461dm.css';
import '../../css/m/mi_d81xnw.css';
import '../../css/k/k_haes9zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_as461dm"/><path class="mi_d81xnw"/><path clip-rule="evenodd" class="k_haes9zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:four-k-outline" /></template>
