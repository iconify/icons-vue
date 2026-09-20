<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sisc4abcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dropper-eye-outline-sharp" /></template>
<style>
.sisc4abcf {
  fill: currentColor;
  d: path("m15.62 9.271l3.23-3.196l-.925-.925l-3.208 3.227zm0 0l-.903-.894zM4 20v-3.366l8.771-8.77l-1.81-1.791l.714-.707l2.329 2.303l3.935-3.953l2.327 2.365l-3.954 3.954l1.823 1.854l-.708.707l-3.942-4.019L5 17.017V19h1.742q.154.28.317.521q.162.24.333.479zm11.135 2q-1.833 0-3.383-.94t-2.483-2.521q.933-1.581 2.483-2.522t3.382-.94t3.383.94T21 18.538q-.933 1.581-2.483 2.521q-1.55.941-3.382.941m2.62-1.67q1.234-.668 2.072-1.791q-.838-1.123-2.072-1.793t-2.62-.669t-2.62.67t-2.073 1.792q.839 1.123 2.073 1.792t2.62.669t2.62-.67m-3.327-1.085q-.294-.293-.294-.707t.294-.706q.293-.294.707-.294q.413 0 .706.294t.294.706t-.294.707t-.707.293t-.706-.293");
}

</style>
