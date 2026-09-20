<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp8c_wbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bike-scooter-sharp" /></template>
<style>
.zp8c_wbck {
  fill: currentColor;
  d: path("M.23 18.5v-1h4.524q.179-1.777 1.422-3.09q1.243-1.314 2.932-1.545L7.485 5.5H3.73v-1h4.565l2.031 9.27H10q-1.766 0-3.017 1.251q-1.252 1.252-1.252 3.017v.462zm8 1.308q-.73-.731-.73-1.77t.73-1.769t1.77-.73t1.77.73t.73 1.77t-.73 1.769t-1.77.73t-1.77-.73m11-2.347q-1.741 0-2.989-1.093T14.754 13.5h-2.696l-.22-1h2.916q.087-.69.51-1.623q.425-.933 1.236-1.416h-5.304l-.219-1h6.035l-1.735-4.73h-2.465v-1h3.179l2.094 5.719h1.146q1.902 0 3.2 1.299t1.3 3.201q0 1.856-1.347 3.184q-1.348 1.327-3.153 1.327m-.693-4.765l.939-.354l-1.038-2.765l-.889.354z");
}

</style>
