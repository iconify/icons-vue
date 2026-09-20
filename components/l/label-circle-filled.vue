<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/k/kvn14gsjy.css';
import '../../css/j/jhjvekb4k.css';
import '../../css/f/fc5tljbzo.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGGF5Yucmb"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="jhjvekb4k"/><path class="fc5tljbzo"/></g></mask></defs><circle mask="url(#SVGGF5Yucmb)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:label-circle-filled" /></template>
