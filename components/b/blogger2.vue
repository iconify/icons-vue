<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcse9kmkw.css';
import '../../css/e/e54jf8rbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jcse9kmkw"/><path class="e54jf8rbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:blogger2" /></template>
