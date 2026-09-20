<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eicjkfb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:decimal-increase-outline-sharp" /></template>
<style>
.eicjkfb5l {
  fill: currentColor;
  d: path("m17.423 20.789l-.707-.689L18.79 18h-6.81v-1h6.81l-2.075-2.1l.707-.688l3.289 3.288zM4.25 12.827v-1.692h1.692v1.692zm3.88-.805q-.803-.806-.803-1.945v-4q0-1.14.806-1.945t1.946-.805t1.944.805t.804 1.945v4q0 1.14-.806 1.945t-1.946.805t-1.944-.805m7.885 0q-.804-.806-.804-1.945v-4q0-1.14.806-1.945t1.946-.805t1.944.805t.803 1.945v4q0 1.14-.805 1.945q-.806.805-1.946.805t-1.945-.805m-4.703-.705q.515-.511.515-1.24v-4q0-.73-.514-1.24q-.515-.51-1.236-.51t-1.236.51q-.514.51-.514 1.24v4q0 .729.514 1.24q.515.51 1.236.51t1.236-.51m7.884 0q.515-.511.515-1.24v-4q0-.73-.515-1.24q-.514-.51-1.235-.51t-1.236.51t-.514 1.24v4q0 .729.514 1.24t1.236.51q.72 0 1.235-.51");
}

</style>
