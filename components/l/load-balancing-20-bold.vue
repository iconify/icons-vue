<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb0q-t_1r.css';
import '../../css/g/g8k86tb-n.css';
import '../../css/k/k-qil1rqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gb0q-t_1r"/><path class="g8k86tb-n"/><path class="k-qil1rqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:load-balancing-20-bold" /></template>
