<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv0vkwb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bike-scooter-outline-sharp" /></template>
<style>
.dv0vkwb7t {
  fill: currentColor;
  d: path("M.23 18.5v-1h4.524q.179-1.777 1.422-3.09q1.243-1.314 2.932-1.545L7.485 5.5H3.73v-1h4.565l2.031 9.27H10q-1.766 0-3.017 1.251q-1.252 1.252-1.252 3.017v.462zm8 1.308q-.73-.731-.73-1.77t.73-1.769t1.77-.73t1.77.73t.73 1.77t-.73 1.769t-1.77.73t-1.77-.73m2.829-.711q.441-.441.441-1.059t-.441-1.058T10 16.538t-1.059.442t-.441 1.058t.441 1.059t1.059.441t1.059-.441m8.172-1.636q-1.743 0-2.99-1.093T14.754 13.5h-2.696l-.22-1h2.916q.087-.69.51-1.623q.425-.933 1.236-1.416h-5.304l-.219-1h6.035l-1.735-4.73h-2.465v-1h3.179l2.094 5.719h1.146q1.902 0 3.2 1.299t1.3 3.201q0 1.856-1.347 3.184q-1.348 1.327-3.153 1.327m0-.961q1.486 0 2.493-1.029T22.731 13q0-1.487-1.007-2.493T19.231 9.5q-.223 0-.416.01t-.377.067l1.039 2.765l-.938.354l-.989-2.765q-.865.483-1.342 1.327T15.73 13q0 1.442 1.007 2.471T19.23 16.5m0-3.5");
}

</style>
