<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/g/g1xg7eiii.css';
import '../../css/g/gzw7gyr6o.css';
import '../../css/s/s1z0bh-al.css';
import '../../css/n/nqy-9n9qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g1xg7eiii"/><path class="gzw7gyr6o"/><path class="s1z0bh-al"/><path class="nqy-9n9qs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cards" /></template>
