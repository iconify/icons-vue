<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb6dvfbbn.css';
import '../../css/a/ajl3hnenw.css';
import '../../css/k/k6canw58a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rb6dvfbbn"/><path class="ajl3hnenw"/><path class="k6canw58a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:git-branch-48" /></template>
