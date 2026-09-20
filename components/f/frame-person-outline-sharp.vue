<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr0q2lmaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:frame-person-outline-sharp" /></template>
<style>
.fr0q2lmaa {
  fill: currentColor;
  d: path("M3 21v-5h1v4h4v1zM3 8V3h5v1H4v4zm13 13v-1h4v-4h1v5zm4-13V4h-4V3h5v5zm-8.002 3.885q-1.042 0-1.77-.728T9.5 9.387q0-1.022.728-1.762t1.77-.74q1.021 0 1.762.74q.74.74.74 1.762q0 1.042-.74 1.77t-1.762.728m.002-1q.617 0 1.059-.432q.441-.431.441-1.068q0-.618-.441-1.059q-.442-.441-1.068-.441t-1.06.441q-.431.441-.431 1.068t.431 1.059t1.069.432m-5.5 6.23v-1.4q0-.402.206-.756t.557-.565q1.074-.636 2.278-.958q1.205-.32 2.459-.32t2.459.32t2.278.958q.352.21.558.565t.205.757v1.4zm3.25-2.673q-1.129.327-2.215.943v.75h8.93v-.77q-1.067-.615-2.206-.932q-1.138-.317-2.259-.317t-2.25.326m4.51 1.693h2.205h-8.93z");
}

</style>
