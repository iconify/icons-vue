<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et8aabb_z.css';
import '../../css/a/akwv6qb5q.css';
import '../../css/v/v539uowyg.css';
import '../../css/o/oqolilywl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="et8aabb_z"/><path class="akwv6qb5q"/><path class="v539uowyg"/><circle class="oqolilywl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:androidstudio" /></template>
