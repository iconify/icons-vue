<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy3pqcxku.css';
import '../../css/g/gy0kacpby.css';
import '../../css/q/qq36dbo-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qy3pqcxku"/><path class="gy0kacpby"/><path class="qq36dbo-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:beats" /></template>
