<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6b2j8btj.css';
import '../../css/w/wrweh8jcs.css';
import '../../css/h/ho0kx1xbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b6b2j8btj"/><path class="wrweh8jcs"/><path class="ho0kx1xbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:database" /></template>
