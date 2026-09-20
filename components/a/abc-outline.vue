<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-ae3_bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:abc-outline" /></template>
<style>
.b-ae3_bgn {
  fill: currentColor;
  d: path("M17.039 14.692q-.328 0-.549-.22q-.22-.222-.22-.549v-3.846q0-.327.22-.548q.222-.221.549-.221h2.845q.327 0 .549.22q.22.222.22.549V11h-.884v-.808h-2.615v3.616h2.615V13h.885v.923q0 .327-.221.548q-.222.221-.549.221zm-7.231 0V9.308h3.615q.327 0 .548.22q.221.222.221.549v1.23q0 .291-.133.463q-.134.172-.444.23q.31.058.444.23q.133.172.133.462v1.231q0 .327-.22.548q-.222.221-.549.221zm.884-3.134h2.616v-1.366h-2.616zm0 2.25h2.616v-1.366h-2.616zm-7.346.884v-4.615q0-.327.221-.548t.548-.221h2.847q.327 0 .548.22q.22.222.22.549v4.615h-.884V13H4.231v1.692zm.885-2.576h2.615v-1.924H4.231z");
}

</style>
