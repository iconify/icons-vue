<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/s1rnuy7eq.css';
import '../../css/f/fxuyefsgp.css';
import '../../css/b/b73ocondb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s1rnuy7eq"/><path class="fxuyefsgp"/><path class="b73ocondb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:kettle" /></template>
