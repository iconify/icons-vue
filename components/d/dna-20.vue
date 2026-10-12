<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spkjwsbgk.css';
import '../../css/f/fr-v3dbag.css';
import '../../css/r/rbkzkvmvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="spkjwsbgk"/><path class="fr-v3dbag"/><path class="rbkzkvmvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dna-20" /></template>
