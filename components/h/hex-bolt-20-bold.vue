<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xerqgrbub.css';
import '../../css/a/audsyabir.css';
import '../../css/v/v6pfx7zrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xerqgrbub"/><path class="audsyabir"/><path class="v6pfx7zrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hex-bolt-20-bold" /></template>
