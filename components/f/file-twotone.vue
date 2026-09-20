<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kilinm.css';
import '../../css/k/kyznsp.css';
import '../../css/k/k50i_c.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-62.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/f/fade-to-1.css';
import '../../css/d/d-_-jasl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kilinm kyznsp"/><path class="k50i_c kyznsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:file-twotone" /></template>
